<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu5395ynk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lu5395ynk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-facebook-outline" /></template>
