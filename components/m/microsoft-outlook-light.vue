<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv5gx-44j.css';
import '../../css/s/sobo_lk1b.css';
import '../../css/h/h33hifd-b.css';
import '../../css/i/i69id4bah.css';
import '../../css/o/ooiwd4u1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lv5gx-44j"/><path class="sobo_lk1b"/><path class="h33hifd-b"/><path class="i69id4bah"/><path class="ooiwd4u1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-outlook-light" /></template>
