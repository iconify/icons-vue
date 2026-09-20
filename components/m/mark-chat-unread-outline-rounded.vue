<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrleg5b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mark-chat-unread-outline-rounded" /></template>
<style>
.xrleg5b3j {
  fill: currentColor;
  d: path("m6.077 17l-1.704 1.704q-.379.379-.876.174T3 18.133V4.616q0-.691.463-1.153T4.616 3h9.346q.213 0 .366.163q.153.162.134.376q-.02.194-.163.327q-.143.134-.337.134H4.616q-.231 0-.424.192T4 4.615v13.03L5.65 16h13.735q.23 0 .423-.192t.192-.423V8.942q0-.213.143-.357t.357-.143t.357.143t.143.357v6.443q0 .69-.462 1.152T19.385 17zM17.231 5.73Q16.5 5 16.5 3.963t.73-1.77t1.77-.73t1.77.73t.73 1.77t-.73 1.769t-1.77.73t-1.77-.73M4 4.616v12.769V4z");
}

</style>
