<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmzp2srzw.css';
import '../../css/a/avn_ef2yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jmzp2srzw"/><path class="avn_ef2yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:verdaccio" /></template>
