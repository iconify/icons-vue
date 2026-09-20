<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edtx_g3bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edtx_g3bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-circle-share" /></template>
