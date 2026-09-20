<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smso1cecy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smso1cecy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:video-minus-filled" /></template>
