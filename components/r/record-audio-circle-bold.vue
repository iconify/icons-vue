<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrtv4rb5l.css';
import '../../css/b/bidl9_apl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrtv4rb5l"/><path clip-rule="evenodd" class="bidl9_apl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:record-audio-circle-bold" /></template>
