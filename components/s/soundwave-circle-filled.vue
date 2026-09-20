<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2sn25lun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v2sn25lun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:soundwave-circle-filled" /></template>
