<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba2ravb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba2ravb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wink-solid" /></template>
