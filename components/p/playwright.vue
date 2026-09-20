<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvv31odee.css';
import '../../css/c/c8c70ibjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvv31odee"/><path class="c8c70ibjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:playwright" /></template>
