<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et211dbdf.css';
import '../../css/a/a9-n70bna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="et211dbdf"/><path class="a9-n70bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-notification" /></template>
