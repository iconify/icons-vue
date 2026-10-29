<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvk2mbcwh.css';
import '../../css/e/egyf9jbvi.css';
import '../../css/g/gs45f_bze.css';
import '../../css/i/icly_ob1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvk2mbcwh"/><path class="egyf9jbvi"/><path class="gs45f_bze"/><path class="icly_ob1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:wifi" /></template>
