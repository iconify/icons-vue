<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azleb5chk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="azleb5chk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:notebook3" /></template>
