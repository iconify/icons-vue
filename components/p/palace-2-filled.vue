<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbah3mb6z.css';
import '../../css/x/xsmw2sb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbah3mb6z"/><path class="xsmw2sb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:palace-2-filled" /></template>
