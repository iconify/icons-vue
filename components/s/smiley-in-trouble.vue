<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhh7etb7m.css';
import '../../css/f/f7yw1h3jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhh7etb7m"/><path class="f7yw1h3jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:smiley-in-trouble" /></template>
