<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj16luh-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:touch-double-2-rounded" /></template>
<style>
.gj16luh-q {
  fill: currentColor;
  d: path("M10.412 21q-.547 0-1.04-.215q-.495-.214-.824-.668l-4.636-5.929q-.11-.165-.104-.35t.146-.327q.31-.309.755-.355q.445-.047.841.182l2.508 1.54V8.193q0-.194.143-.347t.357-.153q.194 0 .347.153t.153.347v3.789h2.269V6.519q0-.194.143-.347t.357-.153q.194 0 .347.153t.153.347v5.462h4.289q.98 0 1.682.702T19 14.366v3.288q0 1.406-.983 2.376t-2.363.97zm.05-18q-1.089 0-2.02.41q-.933.41-1.646 1.123q-.765.765-1.191 1.823t-.341 2.136q.013.214-.119.388t-.326.204t-.361-.1t-.187-.326q-.102-1.32.389-2.61q.49-1.29 1.429-2.229q.834-.835 1.955-1.327T10.462 2t2.417.492t1.956 1.327q.967.968 1.41 2.179t.346 2.579q-.02.214-.16.339t-.352.094t-.339-.18t-.13-.363q.026-1.142-.326-2.124t-1.163-1.81q-.713-.714-1.642-1.124Q11.55 3 10.462 3");
}

</style>
