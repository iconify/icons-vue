<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rojvpmb6a.css';
import '../../css/j/jy3p094dk.css';
import '../../css/j/j_7wf_9wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rojvpmb6a"/><path class="jy3p094dk"/><path class="j_7wf_9wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:study-previous" /></template>
