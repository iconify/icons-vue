<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmizg-b1r.css';
import '../../css/m/mf2faab1e.css';
import '../../css/m/m1bd3mb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmizg-b1r"/><path class="mf2faab1e"/><path class="m1bd3mb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:surprise-line" /></template>
