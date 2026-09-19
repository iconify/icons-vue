<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1xy6nh9u.css';
import '../../css/b/b8gjdvb7r.css';
import '../../css/h/hux66ibbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="n1xy6nh9u"/><path class="b8gjdvb7r"/><path class="hux66ibbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:station" /></template>
