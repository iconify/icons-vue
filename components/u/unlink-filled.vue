<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emm5k3-xc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b emm5k3-xc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:unlink-filled" /></template>
