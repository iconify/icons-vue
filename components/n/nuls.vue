<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifuw65ceo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifuw65ceo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nuls" /></template>
