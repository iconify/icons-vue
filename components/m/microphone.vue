<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ak7mb6b3t.css';
import '../../css/j/jfq3qu33i.css';
import '../../css/z/zlg4ve8af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ak7mb6b3t"/><path class="jfq3qu33i"/><path class="zlg4ve8af"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:microphone" /></template>
