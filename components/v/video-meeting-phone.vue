<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3xtuk_0z.css';
import '../../css/h/hmq1l2vbu.css';
import '../../css/g/g3e1yzbjo.css';
import '../../css/b/bnh6vyb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="l3xtuk_0z"><path class="hmq1l2vbu"/><path class="g3e1yzbjo"/><path class="bnh6vyb7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:video-meeting-phone" /></template>
