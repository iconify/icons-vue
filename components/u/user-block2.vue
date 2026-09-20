<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxvs0utbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xxvs0utbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-block2" /></template>
