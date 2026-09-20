<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw_3-n8mp.css';
import '../../css/x/xu9n3sboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw_3-n8mp"/><path class="xu9n3sboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-talk-filled" /></template>
