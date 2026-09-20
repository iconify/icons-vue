<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbeaf3bzp.css';
import '../../css/b/b3jjboblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jbeaf3bzp"/><path class="b3jjboblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-minus" /></template>
