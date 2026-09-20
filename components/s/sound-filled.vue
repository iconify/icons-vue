<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qldwtj9yi.css';
import '../../css/v/v8mk5pbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qldwtj9yi"/><path class="v8mk5pbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sound-filled" /></template>
