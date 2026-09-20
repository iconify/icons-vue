<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmjhp2sbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmjhp2sbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:wifi-slash-expressive" /></template>
