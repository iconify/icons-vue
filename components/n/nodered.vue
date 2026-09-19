<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va6jvlbzo.css';
import '../../css/y/y0kw6z96g.css';
import '../../css/d/dgq02yorw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="va6jvlbzo"/><path class="y0kw6z96g"/><path class="dgq02yorw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nodered" /></template>
