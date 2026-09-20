<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/maqvnbcnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="maqvnbcnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:zoom-in-area-filled" /></template>
