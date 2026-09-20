<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze6v68axo.css';
import '../../css/r/rii9k4bgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze6v68axo"/><path class="rii9k4bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:vuejs-alt" /></template>
