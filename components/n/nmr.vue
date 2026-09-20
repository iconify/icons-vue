<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2k1m9bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l2k1m9bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nmr" /></template>
