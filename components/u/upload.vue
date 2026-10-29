<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec_0r_tga.css';
import '../../css/n/nx9eqfb9e.css';
import '../../css/a/aloyasbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ec_0r_tga wm-k"/><path class="nx9eqfb9e wm-a"/><path class="aloyasbca wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:upload" /></template>
