<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4gul0b8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b4gul0b8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:screwdriver" /></template>
