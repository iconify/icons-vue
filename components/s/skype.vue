<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0bk0ccsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g0bk0ccsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:skype" /></template>
