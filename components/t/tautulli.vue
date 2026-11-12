<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6df3db1i.css';
import '../../css/b/bw7r1grov.css';
import '../../css/l/lec4rdbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="s6df3db1i"/><path class="bw7r1grov"/><path class="lec4rdbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tautulli" /></template>
