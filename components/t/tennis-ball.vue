<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avomhzplk.css';
import '../../css/x/xrwqa-u3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avomhzplk"/><path class="xrwqa-u3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:tennis-ball" /></template>
