<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imv8u3_9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imv8u3_9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:transaction-yen" /></template>
