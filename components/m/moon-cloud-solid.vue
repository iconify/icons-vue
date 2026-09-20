<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsebaw_qg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bsebaw_qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:moon-cloud-solid" /></template>
