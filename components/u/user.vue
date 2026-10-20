<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdcnc9bhs.css';
import '../../css/x/xi2u7tbob.css';
import '../../css/f/fdzsszb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18.035,"height":17.5};
const content = `<path class="rdcnc9bhs"/><path class="xi2u7tbob"/><path class="fdzsszb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="k8s:user" /></template>
