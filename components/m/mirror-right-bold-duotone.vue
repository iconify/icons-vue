<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa5889vlx.css';
import '../../css/a/aa2olkmfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa5889vlx"/><path clip-rule="evenodd" class="aa2olkmfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mirror-right-bold-duotone" /></template>
