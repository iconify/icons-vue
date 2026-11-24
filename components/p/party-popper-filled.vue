<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emus6-b1j.css';
import '../../css/q/qrb2onfcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="emus6-b1j"/><path class="qrb2onfcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:party-popper-filled" /></template>
