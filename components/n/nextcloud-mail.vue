<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou4p7f2ib.css';
import '../../css/j/jc3uzbbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ou4p7f2ib"/><path class="jc3uzbbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-mail" /></template>
