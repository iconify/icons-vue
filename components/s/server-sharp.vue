<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aje1gjofx.css';
import '../../css/z/z2xdwcchy.css';
import '../../css/o/o-9st-ttp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aje1gjofx"/><path class="z2xdwcchy"/><path class="o-9st-ttp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:server-sharp" /></template>
