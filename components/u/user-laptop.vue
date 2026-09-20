<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lug35-z0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lug35-z0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-laptop" /></template>
