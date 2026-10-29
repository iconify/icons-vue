<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3eha7bzt.css';
import '../../css/r/r3a3c2hpl.css';
import '../../css/w/w5ou4mocx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3eha7bzt wm-k"/><path class="r3a3c2hpl wm-a"/><path class="w5ou4mocx wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:toggle" /></template>
