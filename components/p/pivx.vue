<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4ouod96n.css';
import '../../css/d/dcpdfk6aa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4ouod96n"/><path class="dcpdfk6aa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pivx" /></template>
