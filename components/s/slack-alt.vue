<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r31v6djmg.css';
import '../../css/h/h8wl53bui.css';
import '../../css/c/c7y1ahbub.css';
import '../../css/p/p-n5subdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r31v6djmg"/><path class="h8wl53bui"/><path class="c7y1ahbub"/><path class="p-n5subdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:slack-alt" /></template>
