<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw6dpjb4k.css';
import '../../css/t/t-v91db8t.css';
import '../../css/g/glwfk_a6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw6dpjb4k wm-k"/><path class="t-v91db8t wm-s"/><path class="glwfk_a6x wm-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:remove-formatting" /></template>
