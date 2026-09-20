<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsoddbbnl.css';
import '../../css/w/w-6tn9btk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsoddbbnl"/><path class="w-6tn9btk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:transfer-pictures-sent" /></template>
