<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg4rycc9o.css';
import '../../css/q/qfttfgb8q.css';
import '../../css/d/djyvkb6-g.css';
import '../../css/f/frp7jbb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="sg4rycc9o"/><path class="qfttfgb8q"/><path class="djyvkb6-g"/><path class="frp7jbb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:yii" /></template>
