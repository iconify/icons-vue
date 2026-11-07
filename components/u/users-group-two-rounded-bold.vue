<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lagukibcz.css';
import '../../css/y/yffxg5ktw.css';
import '../../css/b/bi3s7qmxc.css';
import '../../css/b/buif742pl.css';
import '../../css/z/z_0u9humb.css';
import '../../css/c/cfzsbfbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lagukibcz"/><path class="yffxg5ktw"/><path class="bi3s7qmxc"/><path class="buif742pl"/><path class="z_0u9humb"/><path class="cfzsbfbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:users-group-two-rounded-bold" /></template>
