<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pht7-hqwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pht7-hqwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-minus-filled" /></template>
