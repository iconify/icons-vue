<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhnnhc9bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lhnnhc9bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:playerfm-logo-solid" /></template>
