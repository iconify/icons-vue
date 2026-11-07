<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puwao6b5b.css';
import '../../css/j/jcvro1hvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="puwao6b5b"/><path clip-rule="evenodd" class="jcvro1hvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mirror-left-bold-duotone" /></template>
