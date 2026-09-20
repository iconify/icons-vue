<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_kkczf_w.css';
import '../../css/k/kb_awpb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v_kkczf_w"/><path class="kb_awpb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zrok-dark" /></template>
