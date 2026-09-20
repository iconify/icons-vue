<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guc0uebjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guc0uebjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:maildotcom" /></template>
