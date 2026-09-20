<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy1iyyqho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy1iyyqho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pinned" /></template>
