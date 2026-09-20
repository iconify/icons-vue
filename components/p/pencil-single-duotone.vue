<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvm8evbio.css';
import '../../css/z/z9687bcgq.css';
import '../../css/k/ksdi_7b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvm8evbio"/><path class="z9687bcgq"/><path clip-rule="evenodd" class="ksdi_7b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pencil-single-duotone" /></template>
