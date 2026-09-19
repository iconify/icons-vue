<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjn5tlbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wjn5tlbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:ror" /></template>
