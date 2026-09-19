<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nds9cwbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nds9cwbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:unlock-solid" /></template>
