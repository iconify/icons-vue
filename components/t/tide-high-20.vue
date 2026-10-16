<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-93wacki.css';
import '../../css/p/p5711fb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b-93wacki"/><path class="p5711fb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tide-high-20" /></template>
