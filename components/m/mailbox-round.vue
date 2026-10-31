<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g20oe2oyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g20oe2oyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mailbox-round" /></template>
