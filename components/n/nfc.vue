<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc27e2w6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc27e2w6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:nfc" /></template>
