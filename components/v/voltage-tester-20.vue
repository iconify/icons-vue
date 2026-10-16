<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvi0cxbyw.css';
import '../../css/s/suxe2ovzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yvi0cxbyw"/><path class="suxe2ovzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voltage-tester-20" /></template>
