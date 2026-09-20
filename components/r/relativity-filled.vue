<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgae07xbo.css';
import '../../css/r/rr7ezt0es.css';
import '../../css/x/xfjodpqdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgae07xbo"/><path class="rr7ezt0es"/><path class="xfjodpqdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:relativity-filled" /></template>
