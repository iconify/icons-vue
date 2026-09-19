<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad44kbbwp.css';
import '../../css/j/jf9rcrubp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ad44kbbwp"/><path class="jf9rcrubp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-photos" /></template>
