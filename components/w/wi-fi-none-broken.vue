<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghyy-bnrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghyy-bnrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-none-broken" /></template>
