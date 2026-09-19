<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m8ei0x73x.css';
import '../../css/s/s3jbqac2t.css';
import '../../css/e/e616m1bxg.css';
import '../../css/k/kpe56rbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="m8ei0x73x"/><path class="s3jbqac2t"/><path clip-rule="evenodd" class="e616m1bxg"/><path clip-rule="evenodd" class="kpe56rbuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:pile-of-poo" /></template>
