<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfmpvh6sc.css';
import '../../css/g/gr7b__mxd.css';
import '../../css/y/yh-bu38fx.css';
import '../../css/t/tyzbf5qjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfmpvh6sc wm-k"/><path class="gr7b__mxd wm-k"/><path class="wm-a yh-bu38fx"/><path class="tyzbf5qjt wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:newspaper" /></template>
