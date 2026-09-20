<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcs0acnmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcs0acnmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-7" /></template>
