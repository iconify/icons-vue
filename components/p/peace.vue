<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcs10w16x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="lcs10w16x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:peace" /></template>
