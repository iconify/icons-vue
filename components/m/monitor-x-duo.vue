<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k75jqw9vz.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bkhpw8bej.css';
import '../../css/i/izggtwq7w.css';
import '../../css/s/s2nwy5btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k75jqw9vz secondary"/><g class="dt0cm9dhy primary"><path class="bkhpw8bej"/><path class="izggtwq7w"/><path class="s2nwy5btc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:monitor-x-duo" /></template>
