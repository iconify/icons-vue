<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7bxye5gu.css';
import '../../css/f/f0tftrz9n.css';
import '../../css/h/h1bugcb5m.css';
import '../../css/y/yfst6cc1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j7bxye5gu"/><path class="f0tftrz9n"/><path class="h1bugcb5m"/><path class="yfst6cc1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quickbars" /></template>
