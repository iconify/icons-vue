<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqbs8rbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqbs8rbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:usd-coin-usdc-line" /></template>
