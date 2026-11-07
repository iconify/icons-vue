<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2ybt1sxt.css';
import '../../css/s/st7xg9lhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2ybt1sxt"/><path clip-rule="evenodd" class="st7xg9lhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:multiple-forward-left-bold-duotone" /></template>
