<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzthrzbpn.css';
import '../../css/z/zvjeae8vn.css';
import '../../css/t/tdqgqzbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uzthrzbpn"/><path clip-rule="evenodd" class="zvjeae8vn"/><path class="tdqgqzbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:ui-panels-left-right-16" /></template>
