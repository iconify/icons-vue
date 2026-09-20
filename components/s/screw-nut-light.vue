<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgt55-51t.css';
import '../../css/j/jratsslgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgt55-51t"/><path class="jratsslgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:screw-nut-light" /></template>
