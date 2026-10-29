<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu4speh-f.css';
import '../../css/w/w89bx5biq.css';
import '../../css/q/qtghocgwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu4speh-f wm-k"/><path class="w89bx5biq wm-a"/><path class="qtghocgwn wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:video-camera" /></template>
