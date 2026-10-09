<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv56ohh-o.css';
import '../../css/j/jf6r4n4lm.css';
import '../../css/b/bcf5uus5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iv56ohh-o"/><path class="jf6r4n4lm"/><path class="bcf5uus5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:yoga-20" /></template>
