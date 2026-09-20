<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dgh7jhswh"/><circle class="i-68fbbek"/><path class="rr8w5evod"/><ellipse class="eo5xa_pgh"/><path class="ttmrap5ru"/><path class="im_6cp1tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:medical-symbol" /></template>
<style>
.dgh7jhswh {
  fill: var(--svg-color--9266cc, #9266cc);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.eo5xa_pgh {
  cx: 12.307px;
  cy: 6.9px;
  fill: var(--svg-color--9266cc, #9266cc);
  rx: 0.76px;
  ry: 0.442px;
}

.i-68fbbek {
  cx: 18px;
  cy: 4.5px;
  r: 2.5px;
  fill: var(--svg-color--fff, #fff);
}

.im_6cp1tu {
  fill: var(--svg-color--fff, #fff);
  d: path("m17 19.81l2 .379v-8.541l-2-.084zm2 1.979l-2-.369v7.457c.538.065 1.438.277 2 .418zm-2 8.546V33a1 1 0 1 0 2 0v-2.257c-.868-.199-1.422-.278-2-.408m2-19.897V5.33a1 1 0 1 0-2 0v5.016z");
}

.rr8w5evod {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.472 18.27c3.113-.217 9.593-.668 9.593-3.598c0-2.993-6.341-3.215-9.049-3.31l-.305-.011c-10.314-.435-8.543-2.903-7.569-2.903c.274.246 1.189.95 2.71.95c.522 0 1.067-.084 1.62-.251a.23.23 0 0 0 .169-.205a.23.23 0 0 0-.149-.219l-1.461-.577l2.272-.449a.24.24 0 0 0 .176-.137a.22.22 0 0 0-.025-.212c-.052-.068-1.269-1.803-3.355-1.803c-2.849 0-5.141 1.483-5.141 4.039c0 3.09 7.322 3.957 10.597 3.957c6.272 0 6.59.839 6.59 1.007c0 .885-2.227 1.418-6.62 1.585c-4.692.178-7.724 1.501-7.724 3.371c0 1.762 2.272 2.811 7.598 3.508c2.424.317 5.314.85 5.314 1.587c-.001.009-.255.983-5.231 1.605c-4.649.583-5.246 1.677-5.246 2.564c0 1.201 1.697 2.022 5.341 2.582c2.779.427 3.558 1.417 3.932 1.893c.158.2.283.359.499.359c.02 0 .07-.006.089-.01c.207-.048.321-.268.306-.59c-.01-.239-.229-2.357-4.521-3.005c-2.677-.404-2.884-1.048-2.884-1.236c0-.094.12-.58 2.455-.907c.324-.024 7.96-.626 7.96-3.32c0-2.216-4.462-3.023-8.398-3.733c-1.984-.359-4.453-.805-4.453-1.273c.001-.418.852-.976 4.91-1.258");
}

.ttmrap5ru {
  fill: var(--svg-color--9266cc, #9266cc);
  d: path("M16 24.606h1v3.872h-1zm3 0h1v3.872h-1zm-3-9.531h1v3.872h-1zm3 0h1v3.872h-1z");
}

</style>
