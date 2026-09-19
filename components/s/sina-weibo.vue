<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-hm_lb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="k-hm_lb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:sina-weibo" /></template>
