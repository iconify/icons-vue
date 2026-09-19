<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb699of5o.css';
import '../../css/s/s397rccgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eb699of5o"/><path class="s397rccgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-nodejs" /></template>
