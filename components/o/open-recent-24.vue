<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs6ffwolm.css';
import '../../css/o/oiec-xb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs6ffwolm"/><path clip-rule="evenodd" class="oiec-xb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:open-recent-24" /></template>
