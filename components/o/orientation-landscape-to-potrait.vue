<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nybo-p7sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nybo-p7sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:orientation-landscape-to-potrait" /></template>
