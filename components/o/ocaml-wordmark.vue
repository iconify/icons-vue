<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj4l4600f.css';
import '../../css/q/qnh9ymbin.css';
import '../../css/s/s3nt3rbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="nj4l4600f"/><path class="qnh9ymbin"/><path class="s3nt3rbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:ocaml-wordmark" /></template>
