<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc8acmedn.css';
import '../../css/a/altk2-lbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc8acmedn"/><path class="altk2-lbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wind-storm-filled" /></template>
