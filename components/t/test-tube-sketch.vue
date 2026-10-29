<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/epq66ab8j.css';
import '../../css/v/v7mb0kbtd.css';
import '../../css/o/o-pigdbeu.css';
import '../../css/o/okk-zsb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="epq66ab8j"/><path class="v7mb0kbtd wm-k"/><path class="o-pigdbeu wm-k"/><path class="okk-zsb9b wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:test-tube-sketch" /></template>
