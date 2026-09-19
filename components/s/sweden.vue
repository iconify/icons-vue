<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9a76dbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q9a76dbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:sweden" /></template>
