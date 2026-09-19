<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/c-jn_38_e.css';
import '../../css/b/be6sunbbx.css';
import '../../css/y/yut10vb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="c-jn_38_e"/><path class="be6sunbbx"/><path class="yut10vb4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:message-notification-02" /></template>
