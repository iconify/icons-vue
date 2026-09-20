<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c54t2hbrn.css';
import '../../css/j/jvp9h3b4s.css';
import '../../css/g/g3r25me4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c54t2hbrn"/><path class="jvp9h3b4s"/><path clip-rule="evenodd" class="g3r25me4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:npxs" /></template>
