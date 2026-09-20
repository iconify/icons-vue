<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t99-0xbvy.css';
import '../../css/o/ogs-x9j_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t99-0xbvy"/><path clip-rule="evenodd" class="ogs-x9j_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:mic-duotone" /></template>
