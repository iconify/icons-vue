<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et0o79h9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="et0o79h9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-horizontal-outline" /></template>
