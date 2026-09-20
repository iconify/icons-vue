<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypft5mbdm.css';
import '../../css/v/vm4551bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypft5mbdm"/><path class="vm4551bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:phone-add-call-fill" /></template>
