<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw1iew.css';
import '../../css/w/wm-m9w.css';
import '../../css/l/ljka7g.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-82.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew wm-m9w"/><path class="iw1iew ljka7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:mastodon-twotone" /></template>
