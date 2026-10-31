<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr0bi7biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr0bi7biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:red-lantern-gloss" /></template>
