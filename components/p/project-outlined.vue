<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac2-8hbbw.css';
import '../../css/f/f0g9hjb6c.css';
import '../../css/l/l7s1i2bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="ac2-8hbbw"/><path class="f0g9hjb6c"/><path class="l7s1i2bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:project-outlined" /></template>
