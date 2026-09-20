<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/az6u9rb8a.css';
import '../../css/r/r8yg0wt-q.css';
import '../../css/r/r3ctkgbit.css';
import '../../css/g/gdo7kub5u.css';
import '../../css/y/ys9pn8ams.css';
import '../../css/f/f72hono6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="az6u9rb8a"/><path class="r8yg0wt-q"/><path class="r3ctkgbit"/><path class="gdo7kub5u"/><path class="ys9pn8ams"/><path class="f72hono6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:server-line-duotone" /></template>
