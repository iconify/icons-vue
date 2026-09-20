<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1rh2qbtt.css';
import '../../css/o/ow15xdb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1rh2qbtt"/><path class="ow15xdb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-arrow-down-duotone" /></template>
