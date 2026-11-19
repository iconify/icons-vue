<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gimhtxb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gimhtxb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:rooms-nail-salon" /></template>
