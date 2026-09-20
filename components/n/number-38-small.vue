<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dho1bnojv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dho1bnojv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-38-small" /></template>
