<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjq87kk7o.css';
import '../../css/t/taok2ubed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjq87kk7o"/><path clip-rule="evenodd" class="taok2ubed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:panel-left-open-filled" /></template>
