<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq5tr7c8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:voice-chat-off-outline" /></template>
<style>
.cq5tr7c8e {
  fill: currentColor;
  d: path("M19.7 16.966L18.85 16h.535q.269 0 .442-.173t.173-.442V4.615q0-.269-.173-.442T19.385 4H6.85l-1-1h13.535q.69 0 1.153.463T21 4.616v10.769q0 .65-.363 1.041q-.362.391-.937.54m.57 4.719L15.572 17H6.077L3 20.077V4.416L1.008 2.423l.707-.707l19.262 19.261zM4 5.415v12.23L5.65 16h8.935zM6.308 10.5v-1h.884v1zm2.5 2V8.808l.884.884V12.5zm2.75 2v-2.942l.884.884V14.5zm.884-4.908l-.884-.884V5.5h.884zm2.75 2.75l-.884-.884V7.5h.884zm1.616-1.842v-1h.884v1z");
}

</style>
