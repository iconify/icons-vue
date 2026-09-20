<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw_8mpbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw_8mpbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:phone-outgoing" /></template>
