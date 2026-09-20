<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umu-ixchk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umu-ixchk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-1-small" /></template>
