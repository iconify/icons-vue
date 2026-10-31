<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc908bcqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc908bcqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:podium-fill-round" /></template>
