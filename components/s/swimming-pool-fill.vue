<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5qbu8lof.css';
import '../../css/c/ca82trbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b5qbu8lof"/><path class="ca82trbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:swimming-pool-fill" /></template>
