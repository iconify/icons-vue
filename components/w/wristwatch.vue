<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/wbkdetb-c.css';
import '../../css/k/kwm-i6kdf.css';
import '../../css/p/p1ezbcjat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wbkdetb-c"/><path class="kwm-i6kdf"/><path class="p1ezbcjat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:wristwatch" /></template>
