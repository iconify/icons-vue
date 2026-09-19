<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3m690lxe.css';
import '../../css/k/k5sw8vduq.css';
import '../../css/z/z7kdjtbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3m690lxe"/><path clip-rule="evenodd" class="k5sw8vduq"/><path class="z7kdjtbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:sun-outline" /></template>
