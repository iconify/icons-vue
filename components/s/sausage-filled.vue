<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlj6oovbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlj6oovbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sausage-filled" /></template>
