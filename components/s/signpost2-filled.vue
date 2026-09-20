<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aja8p_b7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aja8p_b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:signpost2-filled" /></template>
