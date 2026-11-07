<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtin1i1qt.css';
import '../../css/m/mcs845b1a.css';
import '../../css/h/h9-sbybbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gtin1i1qt"/><path class="mcs845b1a"/><path class="h9-sbybbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:webcam-bold-duotone" /></template>
